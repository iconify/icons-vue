<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcq6a4frh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcq6a4frh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:caret-down-fill" /></template>

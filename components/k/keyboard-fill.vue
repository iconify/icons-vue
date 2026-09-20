<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8umzgbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8umzgbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:keyboard-fill" /></template>

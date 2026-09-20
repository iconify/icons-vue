<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbluk9b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbluk9b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-up-right-square-fill" /></template>

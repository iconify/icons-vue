<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev0k3vk4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="ev0k3vk4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:first-aid" /></template>

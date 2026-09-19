<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv4mebbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv4mebbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laurel-wreath-left-01" /></template>

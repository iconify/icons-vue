<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrfw7f0oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrfw7f0oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-multiple-minus" /></template>

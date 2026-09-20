<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8sq58bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j8sq58bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:horse-solid" /></template>

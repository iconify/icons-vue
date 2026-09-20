<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6w-lk-lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g6w-lk-lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:gamepad-solid" /></template>

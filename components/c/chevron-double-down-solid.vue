<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-u9pu3ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-u9pu3ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-double-down-solid" /></template>

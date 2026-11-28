<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufe5gzu4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufe5gzu4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hot-air-balloon-solid" /></template>

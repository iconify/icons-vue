<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho9g23x-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho9g23x-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:information-serif-circle" /></template>

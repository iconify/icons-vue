<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehueecc9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehueecc9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:certificate-off" /></template>

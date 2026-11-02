<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-cohblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-cohblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gallery-fill" /></template>

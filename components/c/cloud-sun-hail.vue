<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eayb5eiwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eayb5eiwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-sun-hail" /></template>

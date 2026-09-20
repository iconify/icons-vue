<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3a90gpfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3a90gpfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:infinity-fill" /></template>

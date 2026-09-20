<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgkv1oedz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgkv1oedz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:list-bullet-expressive" /></template>

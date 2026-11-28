<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx4061hqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx4061hqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hard-drive-lock" /></template>

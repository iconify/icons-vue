<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enpo_vbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="enpo_vbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-merge-right-filled" /></template>

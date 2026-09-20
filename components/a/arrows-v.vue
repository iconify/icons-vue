<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y56n58bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y56n58bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-v" /></template>

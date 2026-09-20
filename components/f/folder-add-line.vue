<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snhhpl1co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snhhpl1co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-add-line" /></template>

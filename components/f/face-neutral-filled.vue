<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9h80gb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9h80gb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:face-neutral-filled" /></template>

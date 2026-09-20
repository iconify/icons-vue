<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsyuo0y3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsyuo0y3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-up-left" /></template>

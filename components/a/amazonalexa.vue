<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si3f62bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si3f62bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazonalexa" /></template>

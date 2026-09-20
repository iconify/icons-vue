<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icbbfbm-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icbbfbm-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:folder-medical" /></template>

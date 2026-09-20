<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/safc_lb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5.5};
const content = `<path class="safc_lb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:behance" /></template>

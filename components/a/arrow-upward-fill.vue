<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fof7p7mfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fof7p7mfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-upward-fill" /></template>

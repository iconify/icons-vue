<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvcc9_byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvcc9_byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:govee-h6046" /></template>

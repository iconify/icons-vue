<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf6trlnmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf6trlnmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-upload-line" /></template>

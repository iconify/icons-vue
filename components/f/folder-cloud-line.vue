<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0z0yzfqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0z0yzfqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-cloud-line" /></template>

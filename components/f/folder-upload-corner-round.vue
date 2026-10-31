<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gldvn3z1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gldvn3z1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-upload-corner-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn2pokbmn.css';
import '../../css/x/x83nf7g0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn2pokbmn"/><path class="x83nf7g0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-upload-filled" /></template>

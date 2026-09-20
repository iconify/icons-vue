<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0s3r5bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j0s3r5bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:home" /></template>

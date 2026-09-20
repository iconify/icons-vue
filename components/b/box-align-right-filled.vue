<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbnp4i9in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbnp4i9in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-align-right-filled" /></template>

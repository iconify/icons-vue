<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ror_0p-9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ror_0p-9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-media-24" /></template>

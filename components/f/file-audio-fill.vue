<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt6fu6oeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt6fu6oeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-audio-fill" /></template>

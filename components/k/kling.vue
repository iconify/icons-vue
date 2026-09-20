<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6v2n9a-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i6v2n9a-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kling" /></template>

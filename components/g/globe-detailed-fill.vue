<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_h9pdmlz.css';
import '../../css/n/nx_nl5ydl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_h9pdmlz"/><path clip-rule="evenodd" class="nx_nl5ydl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:globe-detailed-fill" /></template>

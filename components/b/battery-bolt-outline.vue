<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikh-14usx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ikh-14usx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-bolt-outline" /></template>

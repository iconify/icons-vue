<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar30v6f3w.css';
import '../../css/r/ra4bz523e.css';
import '../../css/w/wa0xce7qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar30v6f3w"/><circle class="ra4bz523e"/><circle class="wa0xce7qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:browser-outline" /></template>

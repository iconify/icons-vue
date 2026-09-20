<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkn1_fb_t.css';
import '../../css/g/gzawnq-ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="bkn1_fb_t"/><path class="gzawnq-ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:information" /></template>

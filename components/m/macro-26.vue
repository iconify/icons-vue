<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewz6b-n0l.css';
import '../../css/x/x2s3-fbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ewz6b-n0l"/><path class="x2s3-fbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:macro-26" /></template>

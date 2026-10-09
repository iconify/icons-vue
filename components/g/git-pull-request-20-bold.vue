<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6mvyw5ng.css';
import '../../css/w/wmyr2uy2r.css';
import '../../css/b/bei9vou_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n6mvyw5ng"/><path class="wmyr2uy2r"/><path class="bei9vou_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-pull-request-20-bold" /></template>

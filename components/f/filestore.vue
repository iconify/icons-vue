<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvsghrbxx.css';
import '../../css/h/hxj4a-h4s.css';
import '../../css/p/p_x9mhh4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvsghrbxx"/><path class="hxj4a-h4s"/><path class="p_x9mhh4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:filestore" /></template>

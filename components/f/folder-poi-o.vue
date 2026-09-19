<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqrc5kb9t.css';
import '../../css/g/gldcflbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lqrc5kb9t"/><path class="gldcflbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:folder-poi-o" /></template>

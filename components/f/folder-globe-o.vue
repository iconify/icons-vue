<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqrc5kb9t.css';
import '../../css/p/pd_htdb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lqrc5kb9t"/><path class="pd_htdb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:folder-globe-o" /></template>

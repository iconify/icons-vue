<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na-za5bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="na-za5bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-beam" /></template>

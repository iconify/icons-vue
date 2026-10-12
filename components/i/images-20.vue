<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucdqj-bas.css';
import '../../css/m/m3g3pfn4y.css';
import '../../css/m/m2qxt-bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ucdqj-bas"/><path class="m3g3pfn4y"/><path class="m2qxt-bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:images-20" /></template>

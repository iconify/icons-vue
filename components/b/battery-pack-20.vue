<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cco71z33o.css';
import '../../css/i/izilerpqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cco71z33o"/><path class="izilerpqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pack-20" /></template>

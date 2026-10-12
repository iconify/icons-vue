<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szahujb-p.css';
import '../../css/r/rehf-ikcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="rehf-ikcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-zip-20" /></template>

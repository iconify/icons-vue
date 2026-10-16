<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k86i3-bfg.css';
import '../../css/s/sggm0biti.css';
import '../../css/n/nq52osbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k86i3-bfg"/><path class="sggm0biti"/><path class="nq52osbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-input-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9c993b2t.css';
import '../../css/y/yu6hplrgd.css';
import '../../css/w/wfqk8cbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9c993b2t"/><path class="yu6hplrgd"/><path class="wfqk8cbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dryer-48-bold" /></template>

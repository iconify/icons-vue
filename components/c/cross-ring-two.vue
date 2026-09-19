<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak4zvnrpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ak4zvnrpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cross-ring-two" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3szy1brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q3szy1brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bridge-one" /></template>

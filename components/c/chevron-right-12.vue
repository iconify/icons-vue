<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo2aflbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xo2aflbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-right-12" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv2xbp3ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gv2xbp3ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:magsafe-outline" /></template>

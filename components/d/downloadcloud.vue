<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtr2jecan.css';
import '../../css/y/yt81ngblg.css';
import '../../css/f/fkatt9b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="wtr2jecan"/><path class="yt81ngblg"/><path class="fkatt9b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:downloadcloud" /></template>

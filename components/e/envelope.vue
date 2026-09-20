<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq2hylb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qq2hylb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:envelope" /></template>

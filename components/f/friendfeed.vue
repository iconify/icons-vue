<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq4tbcbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":480};
const content = `<path class="vq4tbcbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:friendfeed" /></template>

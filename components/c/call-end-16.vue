<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfmfw0brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lfmfw0brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-end-16" /></template>

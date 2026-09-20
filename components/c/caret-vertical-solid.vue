<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4l_n6szq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b4l_n6szq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:caret-vertical-solid" /></template>

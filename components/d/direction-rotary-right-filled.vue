<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6qay1xjw.css';
import '../../css/b/b0s1w34pd.css';
import '../../css/z/zmh5mjbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="s6qay1xjw"/><path class="b0s1w34pd"/><path class="zmh5mjbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-rotary-right-filled" /></template>

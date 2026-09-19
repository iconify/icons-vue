<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlp6nh86n.css';
import '../../css/n/ng73f_8fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jlp6nh86n"/><path class="ng73f_8fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:globe-favorite" /></template>

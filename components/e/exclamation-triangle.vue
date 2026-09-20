<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzddf_b4l.css';
import '../../css/l/lvp7n1b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzddf_b4l"/><path class="lvp7n1b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:exclamation-triangle" /></template>

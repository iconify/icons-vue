<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtqntyqlm.css';
import '../../css/j/jcqvt8bwl.css';
import '../../css/m/mmwz_gbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtqntyqlm wm-shadow"/><path class="jcqvt8bwl wm-k"/><path class="mmwz_gbga wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-up" /></template>

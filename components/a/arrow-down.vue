<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm-dbpb1d.css';
import '../../css/j/j9dlgjb4r.css';
import '../../css/e/e-p76g1mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm-dbpb1d wm-shadow"/><path class="j9dlgjb4r wm-k"/><path class="e-p76g1mi wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:arrow-down" /></template>

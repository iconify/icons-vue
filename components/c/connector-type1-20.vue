<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_nd-1x5c.css';
import '../../css/x/x6jd1xc0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_nd-1x5c"/><path class="x6jd1xc0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type1-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9-0loj0c.css';
import '../../css/c/cl9-c2b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9-0loj0c"/><path class="cl9-c2b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:code-yellow" /></template>

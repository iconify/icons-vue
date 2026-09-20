<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_su40b-o.css';
import '../../css/a/a46a2oiqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r_su40b-o"/><path class="a46a2oiqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:casino" /></template>

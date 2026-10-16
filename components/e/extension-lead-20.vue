<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av2i24b1f.css';
import '../../css/i/ifjmab6ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="av2i24b1f"/><path class="ifjmab6ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:extension-lead-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvt-etbdx.css';
import '../../css/s/sh3jq6b7q.css';
import '../../css/g/gr0sanbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zvt-etbdx"/><path class="sh3jq6b7q"/><ellipse class="gr0sanbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:camera" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi64kac_w.css';
import '../../css/s/sup9bkb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bi64kac_w"/><path class="sup9bkb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:climbing-frame" /></template>

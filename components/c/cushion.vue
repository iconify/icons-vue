<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of3dkvhwn.css';
import '../../css/v/vn6ed8z0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="of3dkvhwn"/><path class="vn6ed8z0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cushion" /></template>

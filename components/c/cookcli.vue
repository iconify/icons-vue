<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep5i4rb8t.css';
import '../../css/r/rd02-vf7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ep5i4rb8t"/><path class="rd02-vf7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cookcli" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r31wnti5m.css';
import '../../css/d/d_4d0bbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r31wnti5m"/><path class="d_4d0bbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asp-net-core-light" /></template>

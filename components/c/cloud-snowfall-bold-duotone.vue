<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb1w2tbur.css';
import '../../css/e/ejx2y1bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb1w2tbur"/><path class="ejx2y1bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-snowfall-bold-duotone" /></template>

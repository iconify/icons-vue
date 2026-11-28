<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv3gclbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv3gclbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:badge-percent" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhcl_vheq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhcl_vheq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:caret-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx2p0jj_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx2p0jj_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:i3" /></template>

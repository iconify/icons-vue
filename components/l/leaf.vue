<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_bzy_bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_bzy_bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:leaf" /></template>

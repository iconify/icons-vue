<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk1co7rfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk1co7rfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-spot" /></template>

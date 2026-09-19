<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc11kh5kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc11kh5kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hapag-lloyd" /></template>

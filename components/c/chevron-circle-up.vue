<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuqt_yb-q.css';
import '../../css/p/pfj5cj0ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuqt_yb-q"/><path class="pfj5cj0ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:chevron-circle-up" /></template>

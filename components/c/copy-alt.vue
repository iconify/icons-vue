<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn777jbnb.css';
import '../../css/f/ff5-g6s7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn777jbnb"/><path class="ff5-g6s7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:copy-alt" /></template>

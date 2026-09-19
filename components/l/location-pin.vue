<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1t1o_btq.css';
import '../../css/r/r-v6gebze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1t1o_btq"/><path class="r-v6gebze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location-pin" /></template>

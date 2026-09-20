<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co7y88r7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co7y88r7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beestation-dark" /></template>

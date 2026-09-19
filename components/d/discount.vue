<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6fv6ubfm.css';
import '../../css/w/wns-j0bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6fv6ubfm"/><path class="wns-j0bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:discount" /></template>

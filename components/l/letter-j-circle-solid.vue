<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjek9bckt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjek9bckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-j-circle-solid" /></template>

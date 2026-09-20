<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn3hk73hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3hk73hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-k-solid" /></template>

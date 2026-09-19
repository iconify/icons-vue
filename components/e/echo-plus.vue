<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzfj7k4kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzfj7k4kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-plus" /></template>

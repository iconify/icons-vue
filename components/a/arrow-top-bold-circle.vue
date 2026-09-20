<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw2jt_3pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw2jt_3pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-bold-circle" /></template>

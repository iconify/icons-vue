<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqx0khpxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqx0khpxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:corner-left-up" /></template>

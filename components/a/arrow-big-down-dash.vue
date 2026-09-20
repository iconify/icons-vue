<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3fz9hbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3fz9hbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-down-dash" /></template>

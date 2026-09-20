<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2hqi_o1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2hqi_o1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pause-sharp" /></template>

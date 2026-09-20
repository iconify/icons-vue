<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg_t2jbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg_t2jbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-2-filled" /></template>

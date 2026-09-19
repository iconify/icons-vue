<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boah2vobs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boah2vobs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-buckram-three" /></template>

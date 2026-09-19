<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mui3o5b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mui3o5b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:balloon" /></template>

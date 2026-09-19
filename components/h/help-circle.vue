<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyw32fb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyw32fb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:help-circle" /></template>

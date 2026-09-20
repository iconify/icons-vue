<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyfj05bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyfj05bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:link-broken" /></template>

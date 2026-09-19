<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv7-lq6zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv7-lq6zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:liane" /></template>

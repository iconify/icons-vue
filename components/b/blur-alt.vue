<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7f6twbnp.css';
import '../../css/s/s5_vv4szb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7f6twbnp"/><path class="s5_vv4szb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:blur-alt" /></template>

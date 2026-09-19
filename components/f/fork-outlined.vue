<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnq6aobdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnq6aobdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:fork-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqf4-fbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqf4-fbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:iota" /></template>

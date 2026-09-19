<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvw-vvbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvw-vvbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:ghost" /></template>

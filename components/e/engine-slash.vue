<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmvr9pbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmvr9pbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:engine-slash" /></template>

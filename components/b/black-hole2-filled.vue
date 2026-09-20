<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snw6p3bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snw6p3bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:black-hole2-filled" /></template>

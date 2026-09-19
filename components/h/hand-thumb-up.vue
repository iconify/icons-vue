<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9w4_lbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9w4_lbuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-up" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylj5lsb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylj5lsb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fence-off" /></template>

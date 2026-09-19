<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_s0cc7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_s0cc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:beach" /></template>

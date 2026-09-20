<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1bibsy4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1bibsy4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bleach-no-chlorine" /></template>

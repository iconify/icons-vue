<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao9_rtb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao9_rtb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:flag-double" /></template>

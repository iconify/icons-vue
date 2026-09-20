<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1-wfq4rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1-wfq4rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:controls-pause" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjo-xpz6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjo-xpz6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:corner-left-down" /></template>

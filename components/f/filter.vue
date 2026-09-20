<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3svh-r8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3svh-r8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:filter" /></template>

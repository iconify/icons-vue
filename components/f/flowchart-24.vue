<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb6zfvr1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb6zfvr1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:flowchart-24" /></template>

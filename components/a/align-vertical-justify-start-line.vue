<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh4k0b5ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh4k0b5ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-vertical-justify-start-line" /></template>

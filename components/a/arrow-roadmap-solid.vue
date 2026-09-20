<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kul88tp0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kul88tp0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:arrow-roadmap-solid" /></template>

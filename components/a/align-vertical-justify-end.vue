<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lie-7lbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lie-7lbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-vertical-justify-end" /></template>

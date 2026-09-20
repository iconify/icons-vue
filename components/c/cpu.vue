<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmelb9bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmelb9bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cpu" /></template>

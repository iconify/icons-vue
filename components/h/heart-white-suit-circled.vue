<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bntco1b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bntco1b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-white-suit-circled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/latsbryka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="latsbryka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:heart-white-suit" /></template>

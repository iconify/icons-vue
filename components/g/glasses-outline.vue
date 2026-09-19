<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm8ug-bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm8ug-bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:glasses-outline" /></template>

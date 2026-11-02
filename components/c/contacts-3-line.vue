<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc4pz-6xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc4pz-6xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:contacts-3-line" /></template>

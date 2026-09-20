<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4r0djrmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4r0djrmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-bolt" /></template>

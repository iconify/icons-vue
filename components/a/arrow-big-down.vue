<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm2g61bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm2g61bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-big-down" /></template>

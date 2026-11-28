<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqug0npsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqug0npsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-big-right" /></template>

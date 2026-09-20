<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if8f75qhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if8f75qhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:instructables" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa96ic2en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa96ic2en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:direction" /></template>

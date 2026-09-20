<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui60a30tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui60a30tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:list-check-2" /></template>

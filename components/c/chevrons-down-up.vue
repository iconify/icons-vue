<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q00mw2byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q00mw2byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevrons-down-up" /></template>

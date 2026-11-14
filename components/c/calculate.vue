<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9tp0xkkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9tp0xkkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calculate" /></template>

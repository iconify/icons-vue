<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj6hz_b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj6hz_b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:cronos-cro" /></template>

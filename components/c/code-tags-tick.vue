<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptfaom9hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptfaom9hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-tags-tick" /></template>

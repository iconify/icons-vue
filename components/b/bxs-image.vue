<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmtlmrdgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmtlmrdgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-image" /></template>

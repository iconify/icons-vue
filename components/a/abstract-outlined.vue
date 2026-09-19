<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqoi1y9qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqoi1y9qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:abstract-outlined" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6anfqb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y6anfqb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-12-sharp-fill" /></template>

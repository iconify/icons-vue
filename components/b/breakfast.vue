<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1951nb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1951nb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:breakfast" /></template>

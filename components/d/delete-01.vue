<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6hh668-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6hh668-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-01" /></template>

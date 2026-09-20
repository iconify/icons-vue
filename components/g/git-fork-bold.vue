<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg4a_c4ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg4a_c4ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-fork-bold" /></template>

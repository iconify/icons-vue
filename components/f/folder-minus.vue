<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1m4f0bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1m4f0bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-minus" /></template>

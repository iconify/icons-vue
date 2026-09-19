<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8tlmv3ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8tlmv3ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:long-right" /></template>

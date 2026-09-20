<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2asp0b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2asp0b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composetoolbox-light" /></template>

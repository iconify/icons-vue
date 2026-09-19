<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8oih1dmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8oih1dmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-left-small" /></template>

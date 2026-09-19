<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7-rks_4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7-rks_4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-v-alt" /></template>

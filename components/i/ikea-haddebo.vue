<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ad_v4zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ad_v4zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-haddebo" /></template>

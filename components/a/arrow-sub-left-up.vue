<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq4lwtbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq4lwtbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-sub-left-up" /></template>

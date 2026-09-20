<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwtm-ib9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwtm-ib9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:angle-right" /></template>

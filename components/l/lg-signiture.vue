<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfj52-bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfj52-bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lg-signiture" /></template>

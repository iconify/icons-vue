<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e12_dn4ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e12_dn4ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bebo-logo" /></template>

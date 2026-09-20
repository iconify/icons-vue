<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad4e4fb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad4e4fb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-down-broken" /></template>

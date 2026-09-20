<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srcqntbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srcqntbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chair-2-bold" /></template>

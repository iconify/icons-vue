<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6-6guglr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6-6guglr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heading5" /></template>

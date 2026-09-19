<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp6i8pb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp6i8pb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:basket" /></template>

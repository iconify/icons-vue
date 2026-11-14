<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvh8zkukc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvh8zkukc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:5-g-signal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpjsjubje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpjsjubje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:double-arrow-right" /></template>

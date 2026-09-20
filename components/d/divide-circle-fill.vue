<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faioegb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faioegb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:divide-circle-fill" /></template>

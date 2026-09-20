<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi19z5bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi19z5bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-4-fill" /></template>

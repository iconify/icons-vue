<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8rguek9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8rguek9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-left-circle-fill" /></template>

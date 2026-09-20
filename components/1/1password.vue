<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebfq4u1aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebfq4u1aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:1password" /></template>

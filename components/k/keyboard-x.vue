<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp0xepb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp0xepb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:keyboard-x" /></template>

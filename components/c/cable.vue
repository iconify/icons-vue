<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo43c5u5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo43c5u5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cable" /></template>

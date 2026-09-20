<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op6rsqb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op6rsqb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-plus-sharp" /></template>

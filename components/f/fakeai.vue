<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re9h_hbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re9h_hbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fakeai" /></template>

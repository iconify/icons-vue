<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_3b2ob3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_3b2ob3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:document" /></template>

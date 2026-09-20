<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w710jxn7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w710jxn7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:cog" /></template>

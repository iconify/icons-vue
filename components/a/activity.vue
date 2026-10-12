<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4u5-fb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4u5-fb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:activity" /></template>

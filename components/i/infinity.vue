<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhm8-4bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhm8-4bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:infinity" /></template>

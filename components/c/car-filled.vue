<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh22bvbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh22bvbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phcz05bgu.css';
import '../../css/a/a4-kayjwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phcz05bgu"/><path class="a4-kayjwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:car-repair-engine-bold" /></template>

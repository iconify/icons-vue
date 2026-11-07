<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogok9o5lk.css';
import '../../css/w/wzlj4ldvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ogok9o5lk"/><path class="wzlj4ldvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-bold-duotone" /></template>

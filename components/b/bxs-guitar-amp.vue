<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7pmgsrcq.css';
import '../../css/a/ar62u3ixi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7pmgsrcq"/><path class="ar62u3ixi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-guitar-amp" /></template>

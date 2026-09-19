<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix-de3bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ix-de3bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:fly" /></template>

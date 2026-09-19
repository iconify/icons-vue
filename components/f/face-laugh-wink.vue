<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lulf7bc2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lulf7bc2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-laugh-wink" /></template>

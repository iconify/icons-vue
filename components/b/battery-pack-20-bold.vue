<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a12gsqhdy.css';
import '../../css/e/ec3h0kz8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a12gsqhdy"/><path class="ec3h0kz8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pack-20-bold" /></template>

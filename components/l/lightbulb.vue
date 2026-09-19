<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-9y3bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="kj-9y3bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:lightbulb" /></template>

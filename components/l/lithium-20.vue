<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ii7tboz.css';
import '../../css/q/q-j5z09lu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z0ii7tboz"/><path class="q-j5z09lu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lithium-20" /></template>

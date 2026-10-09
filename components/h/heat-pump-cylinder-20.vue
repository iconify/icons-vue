<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r81g9n6kk.css';
import '../../css/s/spi1l0bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r81g9n6kk"/><path class="spi1l0bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-cylinder-20" /></template>

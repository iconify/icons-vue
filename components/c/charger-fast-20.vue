<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr0clkknd.css';
import '../../css/n/nevhvhrth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zr0clkknd"/><path class="nevhvhrth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fast-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0551ib7x.css';
import '../../css/j/jnf1tabyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0551ib7x"/><path class="jnf1tabyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:crop-sharp" /></template>

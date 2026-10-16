<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djp6rcbat.css';
import '../../css/n/n292q15ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="djp6rcbat"/><path class="n292q15ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:eye-closed-20-bold" /></template>

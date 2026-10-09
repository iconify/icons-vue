<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43p6u3yo.css';
import '../../css/t/tp2nuligo.css';
import '../../css/v/vsr49z78k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i43p6u3yo"/><path class="tp2nuligo"/><path class="vsr49z78k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gift-20" /></template>

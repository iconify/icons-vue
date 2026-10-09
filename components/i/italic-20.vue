<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjqwoqbfe.css';
import '../../css/f/fxdh-t-8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pjqwoqbfe"/><path class="fxdh-t-8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:italic-20" /></template>

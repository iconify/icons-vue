<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk9cq9swp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk9cq9swp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:broom" /></template>

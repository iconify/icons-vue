<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub0-4mb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ub0-4mb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:abbrobotstudio" /></template>

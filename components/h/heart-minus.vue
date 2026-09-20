<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izvfm0bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izvfm0bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-minus" /></template>

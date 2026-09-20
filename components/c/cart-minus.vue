<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r08qtsbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r08qtsbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:cart-minus" /></template>

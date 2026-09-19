<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb68hrb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb68hrb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-credit-card-alt" /></template>

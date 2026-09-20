<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlg1ftb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlg1ftb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coupon-sharp-fill" /></template>

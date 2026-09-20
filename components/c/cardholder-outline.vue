<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0imvee_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0imvee_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cardholder-outline" /></template>

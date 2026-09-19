<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czw7ppb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czw7ppb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-up-left-square-solid" /></template>

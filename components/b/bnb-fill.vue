<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcj6_1b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcj6_1b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bnb-fill" /></template>

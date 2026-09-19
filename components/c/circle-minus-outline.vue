<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twz9dj_yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twz9dj_yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:circle-minus-outline" /></template>

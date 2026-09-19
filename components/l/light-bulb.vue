<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hffe1tbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hffe1tbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:light-bulb" /></template>

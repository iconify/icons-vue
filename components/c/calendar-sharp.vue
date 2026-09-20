<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-mj0wift.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-mj0wift"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-sharp" /></template>

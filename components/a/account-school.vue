<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5yoz6nou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5yoz6nou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-school" /></template>

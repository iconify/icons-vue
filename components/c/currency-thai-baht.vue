<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuct18m8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuct18m8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-thai-baht" /></template>

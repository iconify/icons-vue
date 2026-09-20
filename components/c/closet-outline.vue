<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h61y9uz1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h61y9uz1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:closet-outline" /></template>

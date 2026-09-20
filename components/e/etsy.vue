<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vac2kxm0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vac2kxm0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:etsy" /></template>

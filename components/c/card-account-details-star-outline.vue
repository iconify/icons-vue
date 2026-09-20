<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5ne9_xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh5ne9_xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-account-details-star-outline" /></template>

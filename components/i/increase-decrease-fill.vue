<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gql5y_bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gql5y_bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:increase-decrease-fill" /></template>

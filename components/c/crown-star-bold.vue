<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp604pbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp604pbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-star-bold" /></template>

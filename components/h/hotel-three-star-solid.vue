<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvghow68r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvghow68r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hotel-three-star-solid" /></template>

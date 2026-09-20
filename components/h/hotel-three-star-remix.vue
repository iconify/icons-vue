<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avozh9b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="avozh9b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hotel-three-star-remix" /></template>

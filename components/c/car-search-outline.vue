<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwydw2bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwydw2bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-search-outline" /></template>

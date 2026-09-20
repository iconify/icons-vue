<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnmfwi88a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnmfwi88a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-alert" /></template>

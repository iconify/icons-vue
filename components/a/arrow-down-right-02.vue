<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6fkriojo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6fkriojo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-right-02" /></template>

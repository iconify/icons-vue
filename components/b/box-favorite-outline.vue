<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd6tf0onp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd6tf0onp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-favorite-outline" /></template>

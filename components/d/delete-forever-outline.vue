<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8pe9b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8pe9b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-forever-outline" /></template>

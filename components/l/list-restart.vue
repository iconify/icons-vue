<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kytna9nvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kytna9nvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-restart" /></template>

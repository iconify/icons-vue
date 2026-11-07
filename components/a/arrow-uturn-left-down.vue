<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjpgd0j_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjpgd0j_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-left-down" /></template>

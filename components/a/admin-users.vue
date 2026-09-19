<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_flsb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="it_flsb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-users" /></template>

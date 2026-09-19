<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwm-1ccgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwm-1ccgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heart" /></template>

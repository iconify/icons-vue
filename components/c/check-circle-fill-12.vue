<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi-8tsb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pi-8tsb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-circle-fill-12" /></template>

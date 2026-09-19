<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqe0ola9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqe0ola9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:inequality-01" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wly4zwo5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wly4zwo5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building-small-filled" /></template>

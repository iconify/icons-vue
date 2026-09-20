<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s164krv5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s164krv5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:linuxmint" /></template>

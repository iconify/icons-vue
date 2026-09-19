<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx79mzbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx79mzbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:chat" /></template>

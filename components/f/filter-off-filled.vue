<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwmv9riji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwmv9riji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:filter-off-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo7dw8bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo7dw8bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-minimalistic-outline" /></template>

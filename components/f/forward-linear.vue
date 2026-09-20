<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whd7w6bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whd7w6bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-linear" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9jk5xc7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9jk5xc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:globe" /></template>

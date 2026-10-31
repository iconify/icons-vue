<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff75ifvnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff75ifvnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x2-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt08a3bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt08a3bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-left" /></template>

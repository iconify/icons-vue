<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eho36mb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eho36mb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:inbox" /></template>

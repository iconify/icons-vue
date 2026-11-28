<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5b02aceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5b02aceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-left-solid" /></template>

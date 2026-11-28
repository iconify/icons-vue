<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrw5j1c7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrw5j1c7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:alert-double-solid" /></template>

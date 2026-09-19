<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vovxt6bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vovxt6bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:chevron-left" /></template>

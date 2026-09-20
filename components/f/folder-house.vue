<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvkag4bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvkag4bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-house" /></template>

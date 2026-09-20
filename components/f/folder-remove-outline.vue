<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxhu5hnug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxhu5hnug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-remove-outline" /></template>

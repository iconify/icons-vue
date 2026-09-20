<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v43kecc1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v43kecc1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:list-status" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tshyjsb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tshyjsb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hierarchy-files" /></template>

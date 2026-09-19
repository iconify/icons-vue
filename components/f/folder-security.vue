<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka6fx8hhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka6fx8hhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-security" /></template>

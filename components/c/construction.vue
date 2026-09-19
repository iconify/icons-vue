<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pww-_8hki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pww-_8hki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:construction" /></template>

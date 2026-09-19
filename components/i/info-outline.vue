<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcklpyb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcklpyb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:info-outline" /></template>

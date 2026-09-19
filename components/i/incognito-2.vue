<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn9u6kbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn9u6kbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:incognito-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf9dwxbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf9dwxbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:beer" /></template>

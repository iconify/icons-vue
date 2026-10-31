<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm53y-svw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm53y-svw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flag-fill-round" /></template>

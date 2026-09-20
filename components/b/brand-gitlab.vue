<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke-883_3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke-883_3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-gitlab" /></template>

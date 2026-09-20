<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldszo4bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldszo4bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:directus" /></template>

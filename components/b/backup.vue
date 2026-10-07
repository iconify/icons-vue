<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjk479y-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjk479y-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:backup" /></template>

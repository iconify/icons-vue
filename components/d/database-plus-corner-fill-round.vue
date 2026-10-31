<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu5-twbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu5-twbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-plus-corner-fill-round" /></template>

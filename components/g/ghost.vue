<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxaru7c3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxaru7c3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:ghost" /></template>

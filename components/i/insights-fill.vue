<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw4bdl56u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw4bdl56u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:insights-fill" /></template>

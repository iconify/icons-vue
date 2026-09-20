<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xra610bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xra610bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:i18next" /></template>

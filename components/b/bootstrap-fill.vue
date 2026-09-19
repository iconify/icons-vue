<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_agz1bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_agz1bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:bootstrap-fill" /></template>

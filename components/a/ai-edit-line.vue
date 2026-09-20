<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn12tg0us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn12tg0us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-edit-line" /></template>

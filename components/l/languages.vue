<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5qkwxbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5qkwxbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:languages" /></template>

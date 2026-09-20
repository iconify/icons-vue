<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lioq-n8vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lioq-n8vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:close-ring-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzao_8bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzao_8bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-fill" /></template>

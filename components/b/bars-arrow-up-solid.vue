<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kackdgatl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kackdgatl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bars-arrow-up-solid" /></template>

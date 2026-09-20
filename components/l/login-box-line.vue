<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bihk4mb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bihk4mb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:login-box-line" /></template>

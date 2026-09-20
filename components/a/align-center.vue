<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8na7v9av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="m8na7v9av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:align-center" /></template>

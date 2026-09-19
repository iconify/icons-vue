<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fom4vnycj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fom4vnycj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:eye-24px" /></template>

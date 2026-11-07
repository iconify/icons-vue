<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7dkp0b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7dkp0b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-closed-outline" /></template>

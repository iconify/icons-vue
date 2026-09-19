<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufyxqz38e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufyxqz38e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-remove" /></template>

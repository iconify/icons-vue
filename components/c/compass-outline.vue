<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlh451bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlh451bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:compass-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuelcvbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuelcvbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-check-outline" /></template>

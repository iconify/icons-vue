<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lri0ty33y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lri0ty33y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:fountain-filled" /></template>

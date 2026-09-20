<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw3rkdb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw3rkdb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:buildings-fill" /></template>

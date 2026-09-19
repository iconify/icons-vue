<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh4k8abwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh4k8abwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cursor-arrow-rays-solid" /></template>

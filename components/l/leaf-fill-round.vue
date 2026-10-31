<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-5qlccsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-5qlccsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-fill-round" /></template>

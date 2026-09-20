<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvhvk6bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvhvk6bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:angle-right-solid" /></template>

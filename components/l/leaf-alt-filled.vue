<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgru5zbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgru5zbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:leaf-alt-filled" /></template>

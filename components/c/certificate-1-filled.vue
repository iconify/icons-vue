<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5rx9abac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5rx9abac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:certificate-1-filled" /></template>

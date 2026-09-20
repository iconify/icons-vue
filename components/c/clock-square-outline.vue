<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl-5a4gok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl-5a4gok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clock-square-outline" /></template>

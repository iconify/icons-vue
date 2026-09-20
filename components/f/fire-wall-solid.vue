<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9d0qbbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9d0qbbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:fire-wall-solid" /></template>

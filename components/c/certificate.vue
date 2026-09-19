<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aavtj7m5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aavtj7m5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:certificate" /></template>

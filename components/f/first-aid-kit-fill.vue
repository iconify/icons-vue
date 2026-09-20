<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcglpvbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcglpvbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:first-aid-kit-fill" /></template>

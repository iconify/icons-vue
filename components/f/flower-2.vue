<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs4r2bbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="bs4r2bbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:flower-2" /></template>

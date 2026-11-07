<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk94-14if.css';
import '../../css/t/tjyrjeb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk94-14if"/><path clip-rule="evenodd" class="tjyrjeb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:eye-bold" /></template>

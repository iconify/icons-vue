<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czrw65imp.css';
import '../../css/l/ly_zznj_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="czrw65imp"/><path class="ly_zznj_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:condicioner-bold" /></template>

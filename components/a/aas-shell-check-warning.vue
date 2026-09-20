<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h53zl9biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h53zl9biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-check-warning" /></template>

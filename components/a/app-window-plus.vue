<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4nqr853o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4nqr853o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:app-window-plus" /></template>

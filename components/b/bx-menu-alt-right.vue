<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcm6c3j0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcm6c3j0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-menu-alt-right" /></template>

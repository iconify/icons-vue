<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-2qutbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-2qutbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bookmark-alt-plus" /></template>

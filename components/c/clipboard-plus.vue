<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lehcu0c0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lehcu0c0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:clipboard-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evwgfru8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evwgfru8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:21-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_zdk1iax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_zdk1iax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:folder-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd69s5b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd69s5b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-edit-fill" /></template>

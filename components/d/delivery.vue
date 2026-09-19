<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdbtb_gen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdbtb_gen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:delivery" /></template>

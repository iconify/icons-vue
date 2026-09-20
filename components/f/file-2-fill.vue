<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy6z9ubma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy6z9ubma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-2-fill" /></template>

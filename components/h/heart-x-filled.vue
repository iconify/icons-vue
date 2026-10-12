<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zptjmc6mm.css';
import '../../css/v/vb6m8wb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zptjmc6mm"/><path class="vb6m8wb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:heart-x-filled" /></template>

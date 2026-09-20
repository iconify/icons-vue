<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b55gmjb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b55gmjb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-sort-line" /></template>

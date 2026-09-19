<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b616_6bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b616_6bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-console" /></template>

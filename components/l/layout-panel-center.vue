<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jne2jabmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jne2jabmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-panel-center" /></template>

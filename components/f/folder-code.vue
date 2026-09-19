<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acao7vxke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acao7vxke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folder-code" /></template>

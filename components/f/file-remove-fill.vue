<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qudtiwuyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qudtiwuyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:file-remove-fill" /></template>

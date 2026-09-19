<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecisew_dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecisew_dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-remove-thin" /></template>

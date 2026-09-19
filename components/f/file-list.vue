<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emd4_pw8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emd4_pw8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-list" /></template>

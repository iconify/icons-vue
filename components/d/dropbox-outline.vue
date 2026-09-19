<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb4vlibay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cb4vlibay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:dropbox-outline" /></template>

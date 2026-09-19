<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e36ltbb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e36ltbb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:jpg-file-filled" /></template>

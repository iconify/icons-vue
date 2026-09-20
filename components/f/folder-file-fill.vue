<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix2_4ebjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ix2_4ebjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-file-fill" /></template>

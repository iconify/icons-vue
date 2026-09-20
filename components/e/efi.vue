<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy7zoyocc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy7zoyocc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:efi" /></template>

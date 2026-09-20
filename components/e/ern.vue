<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aid4a4bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aid4a4bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ern" /></template>

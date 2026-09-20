<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgrqvsb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgrqvsb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:asterisk-square-remix" /></template>

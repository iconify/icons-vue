<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elagj-87b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="elagj-87b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:caret-left-filled" /></template>

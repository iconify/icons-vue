<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/err-wkw4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="err-wkw4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:idex" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq97rccgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq97rccgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lixx" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-7eiub-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-7eiub-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aqtis" /></template>

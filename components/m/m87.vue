<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rthg1qbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rthg1qbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:m87" /></template>

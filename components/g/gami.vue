<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqo6icbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqo6icbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gami" /></template>

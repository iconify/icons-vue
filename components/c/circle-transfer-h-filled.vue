<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb135jbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb135jbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-transfer-h-filled" /></template>

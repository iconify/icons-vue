<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwvb_sbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwvb_sbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lock-keyhole2-filled" /></template>

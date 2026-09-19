<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhsdat93n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="xhsdat93n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:checkbox-filled" /></template>

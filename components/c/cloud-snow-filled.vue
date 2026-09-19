<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biu392k5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="biu392k5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-snow-filled" /></template>

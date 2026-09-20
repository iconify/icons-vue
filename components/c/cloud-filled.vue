<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hordw4sql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hordw4sql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cloud-filled" /></template>

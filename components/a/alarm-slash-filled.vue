<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv5p8fbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv5p8fbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-slash-filled" /></template>

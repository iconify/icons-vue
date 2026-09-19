<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjh1g7rma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjh1g7rma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ease-in-filled" /></template>

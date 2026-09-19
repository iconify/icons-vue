<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_o-u7b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="b_o-u7b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:button-filled" /></template>

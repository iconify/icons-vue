<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_n7dobql.css';
import '../../css/l/lidjc4bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_n7dobql"/><path class="lidjc4bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:future" /></template>

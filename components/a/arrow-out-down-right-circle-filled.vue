<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-gja2bhg.css';
import '../../css/k/kpu7t4bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-gja2bhg"/><path class="kpu7t4bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-right-circle-filled" /></template>

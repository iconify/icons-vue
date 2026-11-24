<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaxmjgbje.css';
import '../../css/e/eqpz_zlhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxmjgbje"/><path class="eqpz_zlhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-output-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqtcx2bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqtcx2bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disabled-line" /></template>

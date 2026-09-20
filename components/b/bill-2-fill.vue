<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu7fcdc-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu7fcdc-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bill-2-fill" /></template>

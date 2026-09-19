<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkcsv_q9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nkcsv_q9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:edit-markup" /></template>

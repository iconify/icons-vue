<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzlg7-htb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzlg7-htb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-check" /></template>

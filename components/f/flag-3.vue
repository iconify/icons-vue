<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izlg_obuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izlg_obuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-3" /></template>

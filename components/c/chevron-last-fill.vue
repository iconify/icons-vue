<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odlg4gbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odlg4gbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevron-last-fill" /></template>

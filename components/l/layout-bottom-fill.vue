<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btp-w9hcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btp-w9hcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdj9rfmtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdj9rfmtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:database-migration-outlined" /></template>

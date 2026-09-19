<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-a338bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-a338bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:female-outline-24px" /></template>

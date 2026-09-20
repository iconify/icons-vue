<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3yq9dhzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3yq9dhzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-outline" /></template>

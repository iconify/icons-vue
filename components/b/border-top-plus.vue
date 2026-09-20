<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cai9s6bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cai9s6bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:border-top-plus" /></template>

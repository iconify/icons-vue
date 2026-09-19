<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uob0f-byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uob0f-byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:edit-outline" /></template>

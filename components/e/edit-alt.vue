<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddaedubdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddaedubdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:edit-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1coxgz9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1coxgz9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-alt-2-filled" /></template>

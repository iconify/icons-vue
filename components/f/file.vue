<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z132mnbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z132mnbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file" /></template>

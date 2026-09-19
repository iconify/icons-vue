<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy67-5b5k.css';
import '../../css/z/z132mnbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy67-5b5k"/><path class="z132mnbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-code" /></template>

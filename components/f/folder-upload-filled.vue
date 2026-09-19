<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk994-b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk994-b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-upload-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jackfjb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jackfjb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:attachments-filled" /></template>

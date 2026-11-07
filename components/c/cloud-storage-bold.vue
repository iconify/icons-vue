<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-dy5b1v.css';
import '../../css/z/zxk2nibyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd-dy5b1v"/><path class="zxk2nibyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-storage-bold" /></template>

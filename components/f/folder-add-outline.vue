<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2nst-b0v.css';
import '../../css/g/gx2betbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2nst-b0v"/><path class="gx2betbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:folder-add-outline" /></template>

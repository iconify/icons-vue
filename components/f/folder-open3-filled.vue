<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oprl6lmeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oprl6lmeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-open3-filled" /></template>

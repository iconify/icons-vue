<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbpe4x0tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbpe4x0tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:folder-fill" /></template>

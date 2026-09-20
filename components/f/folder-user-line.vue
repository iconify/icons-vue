<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekiu8gmyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekiu8gmyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-user-line" /></template>

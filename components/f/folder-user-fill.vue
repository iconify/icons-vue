<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opccw0okt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opccw0okt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-user-fill" /></template>

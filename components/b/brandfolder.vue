<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxc81zbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxc81zbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:brandfolder" /></template>

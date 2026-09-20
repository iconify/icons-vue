<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv8utaczp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv8utaczp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:folder-hold" /></template>

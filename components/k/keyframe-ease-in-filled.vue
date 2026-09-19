<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/locm-c1zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="locm-c1zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-ease-in-filled" /></template>

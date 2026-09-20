<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbv_j9a6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbv_j9a6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:eljueves" /></template>

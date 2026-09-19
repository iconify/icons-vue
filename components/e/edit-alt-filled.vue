<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veoyribty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veoyribty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:edit-alt-filled" /></template>

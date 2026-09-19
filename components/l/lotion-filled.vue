<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq0nabcok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq0nabcok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lotion-filled" /></template>

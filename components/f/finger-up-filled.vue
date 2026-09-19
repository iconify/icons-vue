<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8txsgbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8txsgbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-up-filled" /></template>

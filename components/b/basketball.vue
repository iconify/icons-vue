<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw7zggb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw7zggb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:basketball" /></template>

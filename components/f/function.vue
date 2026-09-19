<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6s3j1bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6s3j1bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:function" /></template>

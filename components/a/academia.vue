<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs28-1_yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs28-1_yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:academia" /></template>

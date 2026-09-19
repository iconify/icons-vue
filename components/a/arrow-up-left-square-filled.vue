<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar8hrtdvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8hrtdvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-square-filled" /></template>

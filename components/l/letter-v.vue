<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyb6_ersx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyb6_ersx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-v" /></template>

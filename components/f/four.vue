<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps4efgzki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps4efgzki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:four" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpj9vf5jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpj9vf5jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-round-x16-24px" /></template>

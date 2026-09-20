<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pro3-no3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pro3-no3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:like2-filled" /></template>

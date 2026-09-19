<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzri4eb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzri4eb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hot" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfwzuib8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfwzuib8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bone-off" /></template>

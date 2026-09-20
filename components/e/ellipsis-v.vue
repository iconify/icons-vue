<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7v99r1ym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7v99r1ym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:ellipsis-v" /></template>

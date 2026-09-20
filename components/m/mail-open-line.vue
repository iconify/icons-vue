<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfq6du_me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfq6du_me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-open-line" /></template>

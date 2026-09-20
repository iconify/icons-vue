<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3b1qrbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3b1qrbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:android-alt" /></template>

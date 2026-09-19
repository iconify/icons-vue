<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a56fe55pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a56fe55pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chat-solid" /></template>

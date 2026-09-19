<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk3akactx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yk3akactx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:info" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk3anbc7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vk3anbc7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:backward" /></template>

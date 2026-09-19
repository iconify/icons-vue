<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh8p9kf-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yh8p9kf-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-uturn-down-circle-fill" /></template>

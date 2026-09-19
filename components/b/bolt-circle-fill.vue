<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-nawib5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x-nawib5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bolt-circle-fill" /></template>

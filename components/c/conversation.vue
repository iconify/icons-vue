<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssv2w4v0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="ssv2w4v0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:conversation" /></template>

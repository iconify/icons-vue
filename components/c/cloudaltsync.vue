<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv_0-ekbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="uv_0-ekbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cloudaltsync" /></template>

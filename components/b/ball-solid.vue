<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwjm1rblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xwjm1rblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ball-solid" /></template>

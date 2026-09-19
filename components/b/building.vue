<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyko8xbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qyko8xbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:building" /></template>

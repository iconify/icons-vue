<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcvv1xbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":20};
const content = `<path class="rcvv1xbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:discord" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nejg-xwoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nejg-xwoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dadabik" /></template>

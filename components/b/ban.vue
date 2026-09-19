<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7u48b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lv7u48b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ban" /></template>

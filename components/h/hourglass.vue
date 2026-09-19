<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfm84o1-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="bfm84o1-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hourglass" /></template>

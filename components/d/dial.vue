<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un1x6sg7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="un1x6sg7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:dial" /></template>

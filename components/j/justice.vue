<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-rswabiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":392,"height":448};
const content = `<path class="c-rswabiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:justice" /></template>

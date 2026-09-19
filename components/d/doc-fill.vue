<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ashe6sbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ashe6sbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-fill" /></template>

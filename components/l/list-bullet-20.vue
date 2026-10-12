<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyc9a_bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qyc9a_bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-bullet-20" /></template>

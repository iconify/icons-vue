<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmkrdm4ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vmkrdm4ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:call-out" /></template>

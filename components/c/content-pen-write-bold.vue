<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw9bk3v8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw9bk3v8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:content-pen-write-bold" /></template>

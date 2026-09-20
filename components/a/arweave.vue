<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr33f7nqp.css';
import '../../css/a/afu1s7q2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr33f7nqp"/><path class="afu1s7q2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arweave" /></template>

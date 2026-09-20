<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvqusacuk.css';
import '../../css/b/bfknv0bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqusacuk"/><path class="bfknv0bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-alt-circle-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7u-ef1mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7u-ef1mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flash2" /></template>

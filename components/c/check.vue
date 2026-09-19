<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeeq3hpby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeeq3hpby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:check" /></template>

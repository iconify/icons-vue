<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en5m6dbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en5m6dbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlebard" /></template>

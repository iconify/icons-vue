<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu7zw0bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu7zw0bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:laptop" /></template>

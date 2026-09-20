<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85pw7beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f85pw7beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:highlight-off" /></template>

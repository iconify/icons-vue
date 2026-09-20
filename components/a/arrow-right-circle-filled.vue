<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqbaauboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqbaauboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-circle-filled" /></template>

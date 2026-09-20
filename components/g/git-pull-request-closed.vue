<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it66n4bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it66n4bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:git-pull-request-closed" /></template>

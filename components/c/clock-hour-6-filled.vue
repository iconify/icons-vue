<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9cqabcqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9cqabcqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-6-filled" /></template>

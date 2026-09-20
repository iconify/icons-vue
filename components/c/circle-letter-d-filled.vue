<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byv9a6byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byv9a6byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-d-filled" /></template>

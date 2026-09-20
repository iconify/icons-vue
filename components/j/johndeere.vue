<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9wk8624s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9wk8624s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:johndeere" /></template>

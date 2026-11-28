<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac3gkccvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac3gkccvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-right-left-offset" /></template>

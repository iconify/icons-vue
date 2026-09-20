<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5-9mdbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5-9mdbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-arrow-up-sharp" /></template>

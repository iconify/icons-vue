<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaerloj6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaerloj6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-x-sharp" /></template>

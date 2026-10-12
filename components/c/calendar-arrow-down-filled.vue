<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g647b6wru.css';
import '../../css/a/abpmulcbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g647b6wru"/><path class="abpmulcbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-arrow-down-filled" /></template>

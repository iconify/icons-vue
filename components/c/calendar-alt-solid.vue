<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg8faqbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8faqbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:calendar-alt-solid" /></template>

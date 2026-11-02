<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/betak53lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="betak53lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-open-check-fill" /></template>

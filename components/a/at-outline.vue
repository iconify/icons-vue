<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn7jw0bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cn7jw0bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:at-outline" /></template>

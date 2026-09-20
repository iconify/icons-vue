<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl6g29bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl6g29bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-s-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwdovkx8c.css';
import '../../css/w/w3nlvcvue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwdovkx8c"/><path class="w3nlvcvue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-search-filled" /></template>

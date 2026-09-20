<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/horse9bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="horse9bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:book-filled" /></template>

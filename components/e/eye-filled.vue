<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro6ec6buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro6ec6buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eye-filled" /></template>

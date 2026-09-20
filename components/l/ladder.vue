<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eswu5sbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eswu5sbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ladder" /></template>

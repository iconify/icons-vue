<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxeiy3-qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxeiy3-qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-w-octagon-solid" /></template>

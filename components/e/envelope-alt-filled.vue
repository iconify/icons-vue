<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x072svvsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x072svvsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:envelope-alt-filled" /></template>

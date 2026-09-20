<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac7nixbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac7nixbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-crack-fill" /></template>

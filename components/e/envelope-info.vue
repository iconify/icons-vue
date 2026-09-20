<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue7a0iekt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue7a0iekt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-info" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtiq49-zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtiq49-zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-arrow-up-sharp" /></template>

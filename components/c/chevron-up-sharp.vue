<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r71waub-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r71waub-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-up-sharp" /></template>

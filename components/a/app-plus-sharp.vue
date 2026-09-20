<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpoekowgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpoekowgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-plus-sharp" /></template>

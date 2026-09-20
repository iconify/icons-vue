<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o877mybgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o877mybgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-1-sharp-fill" /></template>

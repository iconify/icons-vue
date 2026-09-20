<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duhnwsbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duhnwsbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bug-sharp" /></template>

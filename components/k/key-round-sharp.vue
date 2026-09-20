<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juvi3mbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juvi3mbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:key-round-sharp" /></template>

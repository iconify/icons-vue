<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm5s8mbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fm5s8mbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-g" /></template>

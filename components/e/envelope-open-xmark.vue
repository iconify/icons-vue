<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhazw7j6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jhazw7j6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:envelope-open-xmark" /></template>

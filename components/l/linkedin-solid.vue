<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v568gcbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="v568gcbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:linkedin-solid" /></template>

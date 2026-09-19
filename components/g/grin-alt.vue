<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4v37gz8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="g4v37gz8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-alt" /></template>

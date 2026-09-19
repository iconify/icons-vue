<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7rw7l88j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="i7rw7l88j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-squint" /></template>

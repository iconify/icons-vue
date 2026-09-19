<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptb63ubmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ptb63ubmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:logo-google-text" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs7vf_bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hs7vf_bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:envelope-letter" /></template>

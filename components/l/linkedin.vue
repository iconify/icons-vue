<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq7v8iwzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1504};
const content = `<path class="qq7v8iwzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:linkedin" /></template>

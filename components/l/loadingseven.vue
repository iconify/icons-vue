<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4tk_vyux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f4tk_vyux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:loadingseven" /></template>

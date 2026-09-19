<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5ld2picv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="s5ld2picv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:knife" /></template>

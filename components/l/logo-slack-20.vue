<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bacuuobnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bacuuobnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-slack-20" /></template>

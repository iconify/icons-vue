<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wle5_hbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1568};
const content = `<path class="wle5_hbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:ban" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qugofnbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1792};
const content = `<path class="qugofnbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:i-cursor" /></template>

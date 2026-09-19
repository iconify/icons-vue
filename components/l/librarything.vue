<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q19f3yg1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q19f3yg1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:librarything" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odq-7dbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="odq-7dbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brailleone" /></template>

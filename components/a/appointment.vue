<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n22aambcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="n22aambcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:appointment" /></template>

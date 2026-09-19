<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knp3hqltq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":472};
const content = `<path class="knp3hqltq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:attachment" /></template>

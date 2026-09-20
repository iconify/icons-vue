<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_obz_htu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b_obz_htu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:book-open" /></template>

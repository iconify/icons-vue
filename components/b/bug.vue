<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssho5bc1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ssho5bc1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bug" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zny6c7bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zny6c7bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:book-check-solid" /></template>

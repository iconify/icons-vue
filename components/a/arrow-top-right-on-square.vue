<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn1pczm7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn1pczm7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-top-right-on-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fst7lybqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="fst7lybqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:deletefolder" /></template>

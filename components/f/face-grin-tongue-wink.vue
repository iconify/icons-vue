<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o44rubcqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o44rubcqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-tongue-wink" /></template>

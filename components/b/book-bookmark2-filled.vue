<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3z_ju9sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3z_ju9sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book-bookmark2-filled" /></template>

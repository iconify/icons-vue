<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcztpib1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="tcztpib1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:0" /></template>

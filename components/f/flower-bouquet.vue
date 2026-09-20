<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uarvm0bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uarvm0bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flower-bouquet" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r40p3-bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="r40p3-bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:divide" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab2onr1te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ab2onr1te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:exclamationmark-square-fill" /></template>

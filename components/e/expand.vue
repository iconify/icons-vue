<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5kfwsb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c5kfwsb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:expand" /></template>

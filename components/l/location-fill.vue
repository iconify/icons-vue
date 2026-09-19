<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdwsqwc8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mdwsqwc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:location-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6uk8ob_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h6uk8ob_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:eye-slash" /></template>

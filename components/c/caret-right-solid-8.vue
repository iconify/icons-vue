<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9x-35b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g9x-35b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:caret-right-solid-8" /></template>

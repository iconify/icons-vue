<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0u3k0lff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g0u3k0lff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:diagnostic" /></template>

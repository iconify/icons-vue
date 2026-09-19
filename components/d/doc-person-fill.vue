<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6jpqp12d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i6jpqp12d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-person-fill" /></template>

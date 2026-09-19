<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oex6o5b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oex6o5b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:envelope-open" /></template>

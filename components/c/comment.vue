<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo1lg9b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yo1lg9b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:comment" /></template>

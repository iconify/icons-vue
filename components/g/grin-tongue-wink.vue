<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1cyggo8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="v1cyggo8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-tongue-wink" /></template>

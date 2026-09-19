<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8l0bzpzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="m8l0bzpzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:batteryaltfull" /></template>

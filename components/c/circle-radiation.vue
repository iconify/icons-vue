<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbf5acc-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pbf5acc-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-radiation" /></template>

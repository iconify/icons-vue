<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjqrfbbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bjqrfbbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:laptop-solid" /></template>

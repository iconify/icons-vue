<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk0u74sbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk0u74sbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cassette" /></template>

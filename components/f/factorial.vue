<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/surxv0b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="surxv0b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:factorial" /></template>

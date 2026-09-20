<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f74jxld_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="f74jxld_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:indent-decrease-solid" /></template>

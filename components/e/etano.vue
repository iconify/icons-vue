<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixgen_bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":832};
const content = `<path class="ixgen_bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:etano" /></template>

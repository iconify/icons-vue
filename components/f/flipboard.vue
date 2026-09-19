<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnxjdxlle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="lnxjdxlle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flipboard" /></template>

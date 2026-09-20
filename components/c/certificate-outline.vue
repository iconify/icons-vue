<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aevw-3k9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aevw-3k9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:certificate-outline" /></template>

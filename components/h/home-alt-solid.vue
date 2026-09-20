<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv1zpjeyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kv1zpjeyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:home-alt-solid" /></template>

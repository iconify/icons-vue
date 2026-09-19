<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrucu7bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1344};
const content = `<path class="lrucu7bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gift" /></template>

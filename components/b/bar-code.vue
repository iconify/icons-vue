<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aylov_bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aylov_bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bar-code" /></template>

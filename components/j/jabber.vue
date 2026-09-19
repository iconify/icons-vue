<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v43-w8bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":667.188,"height":1000};
const content = `<path class="v43-w8bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:jabber" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv_jfuboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kv_jfuboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-collar-and-droplet" /></template>

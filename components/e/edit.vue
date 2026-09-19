<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5n66-bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g5n66-bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:edit" /></template>

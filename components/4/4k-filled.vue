<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asbr8qs0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="asbr8qs0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:4k-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/d/d74lauv0c.css';
import '../../css/z/z8f40li9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="d74lauv0c"/><path class="z8f40li9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:impeller-20-bold" /></template>

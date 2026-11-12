<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2wxgo90t.css';
import '../../css/e/efcj-jnsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2wxgo90t"/><path class="efcj-jnsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fava-dark" /></template>

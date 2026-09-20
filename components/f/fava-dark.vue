<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2wxgo90t.css';
import '../../css/b/bo9f9s_he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w2wxgo90t"/><path class="bo9f9s_he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fava-dark" /></template>

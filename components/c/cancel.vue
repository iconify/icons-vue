<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdx40_0pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="gdx40_0pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:cancel" /></template>

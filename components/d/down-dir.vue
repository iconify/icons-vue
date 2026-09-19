<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr5qjmbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":529,"height":1000};
const content = `<path class="cr5qjmbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:down-dir" /></template>

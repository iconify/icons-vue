<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfq0e50ja.css';
import '../../css/n/nc-7gwy-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qfq0e50ja"/><path class="nc-7gwy-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:hide" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8im5qk_h.css';
import '../../css/o/o-a5-mvmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w8im5qk_h"/><path class="o-a5-mvmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-code-20-bold" /></template>

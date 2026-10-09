<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kko00cc3q.css';
import '../../css/f/fpxrp7fka.css';
import '../../css/e/e_u3u9v2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kko00cc3q"/><path class="fpxrp7fka"/><path class="e_u3u9v2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:district-heating-20" /></template>

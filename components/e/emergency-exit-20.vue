<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghoo0wryx.css';
import '../../css/a/a7p7lmknu.css';
import '../../css/i/iipwn-b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ghoo0wryx"/><path class="a7p7lmknu"/><path class="iipwn-b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emergency-exit-20" /></template>

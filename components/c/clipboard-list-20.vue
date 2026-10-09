<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-os2b_i.css';
import '../../css/n/n3ia57pse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xg-os2b_i"/><path class="n3ia57pse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-list-20" /></template>

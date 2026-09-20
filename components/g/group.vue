<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btm1bkawd.css';
import '../../css/x/x-53_-bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="btm1bkawd"/><path class="x-53_-bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:group" /></template>

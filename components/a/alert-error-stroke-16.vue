<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hde0f9hoe.css';
import '../../css/j/jkfvpr2gm.css';
import '../../css/p/p9hlq3xpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><circle class="hde0f9hoe"/><path class="jkfvpr2gm"/></g><circle class="p9hlq3xpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-error-stroke-16" /></template>

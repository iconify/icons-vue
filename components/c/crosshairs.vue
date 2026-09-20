<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiqygcc1r.css';
import '../../css/a/a5ptkn1rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kiqygcc1r"/><path class="a5ptkn1rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:crosshairs" /></template>

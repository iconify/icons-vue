<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uovdbjbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uovdbjbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward-90" /></template>

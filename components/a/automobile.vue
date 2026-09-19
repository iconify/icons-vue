<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ciupeob0b.css';
import '../../css/e/evzchhb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciupeob0b"/><path class="evzchhb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:automobile" /></template>

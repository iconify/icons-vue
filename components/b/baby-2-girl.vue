<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf8jonbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf8jonbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:baby-2-girl" /></template>

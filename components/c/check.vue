<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz48-8bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pz48-8bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:check" /></template>

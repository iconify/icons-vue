<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx0m9s7_b.css';
import '../../css/i/igandw20i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wx0m9s7_b"/><path clip-rule="evenodd" class="igandw20i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:discord-solid" /></template>

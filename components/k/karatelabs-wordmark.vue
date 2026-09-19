<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swdppqbue.css';
import '../../css/e/e_lvdb_ov.css';
import '../../css/j/j7iar1btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="swdppqbue"/><path class="e_lvdb_ov"/><path class="j7iar1btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:karatelabs-wordmark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3apx84gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="n3apx84gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:krakenjs" /></template>

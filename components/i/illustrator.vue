<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm581lbny.css';
import '../../css/v/v7vmxtb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fm581lbny"/><path class="v7vmxtb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:illustrator" /></template>

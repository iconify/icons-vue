<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4kmxzbqa.css';
import '../../css/m/m2awv3b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l4kmxzbqa"/><path class="m2awv3b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:godot" /></template>

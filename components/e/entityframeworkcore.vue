<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyl5gmbif.css';
import '../../css/f/f5bhpxvdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gyl5gmbif"/><path class="f5bhpxvdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:entityframeworkcore" /></template>

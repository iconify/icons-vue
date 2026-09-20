<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ytx1huk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="k5ytx1huk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:k3os" /></template>

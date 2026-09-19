<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5rupt_8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="v5rupt_8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dot-net" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lweui9bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lweui9bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:elixir" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efz0tq6mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="efz0tq6mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:javascript" /></template>

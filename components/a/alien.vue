<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp05z3bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp05z3bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:alien" /></template>

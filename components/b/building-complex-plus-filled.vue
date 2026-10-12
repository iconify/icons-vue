<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yismpnbbv.css';
import '../../css/p/pddla0b_d.css';
import '../../css/g/gcy3r1rbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yismpnbbv"/><path clip-rule="evenodd" class="pddla0b_d"/><path class="gcy3r1rbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:building-complex-plus-filled" /></template>

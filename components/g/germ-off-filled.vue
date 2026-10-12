<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmke0045g.css';
import '../../css/f/fdkgd3bwq.css';
import '../../css/p/pfkyy-b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmke0045g"/><path class="fdkgd3bwq"/><path class="pfkyy-b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:germ-off-filled" /></template>

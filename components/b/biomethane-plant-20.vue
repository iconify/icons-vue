<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya43y5wia.css';
import '../../css/g/g0ni6vb5b.css';
import '../../css/r/r1okuabsg.css';
import '../../css/g/gfj36ibpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ya43y5wia"/><path class="g0ni6vb5b"/><path class="r1okuabsg"/><path class="gfj36ibpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biomethane-plant-20" /></template>

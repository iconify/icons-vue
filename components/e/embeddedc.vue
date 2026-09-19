<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk2hbr6ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zk2hbr6ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:embeddedc" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk7r_jbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zk7r_jbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:adult" /></template>

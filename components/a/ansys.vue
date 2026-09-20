<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4nlze-9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4nlze-9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ansys" /></template>

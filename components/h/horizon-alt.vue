<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7y00378n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="c7y00378n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:horizon-alt" /></template>

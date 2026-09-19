<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x80f4s0za.css';
import '../../css/y/yu1gnvz7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x80f4s0za"/><path class="yu1gnvz7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:container-outlined" /></template>

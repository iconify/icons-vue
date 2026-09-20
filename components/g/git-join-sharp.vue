<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg447v4ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg447v4ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-join-sharp" /></template>

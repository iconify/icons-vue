<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvp031i9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvp031i9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:corner-left-down" /></template>

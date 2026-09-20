<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk_o3uory.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk_o3uory"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npmh_5sus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="npmh_5sus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-alt-02" /></template>

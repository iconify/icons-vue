<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv2madb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gv2madb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:home-alt-02" /></template>

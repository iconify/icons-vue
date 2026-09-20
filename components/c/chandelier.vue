<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnrkt7b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnrkt7b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chandelier" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqoqndb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uqoqndb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:breakfast-filled" /></template>

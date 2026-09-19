<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1ol9kbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1ol9kbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:devices" /></template>

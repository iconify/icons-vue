<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgmt3t6qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgmt3t6qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:luggage" /></template>

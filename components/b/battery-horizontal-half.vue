<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9-u38b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9-u38b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:battery-horizontal-half" /></template>

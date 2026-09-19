<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvk1-n9_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvk1-n9_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:edit-line" /></template>

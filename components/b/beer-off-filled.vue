<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5h4mibrn.css';
import '../../css/b/bopimfhwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5h4mibrn"/><path class="bopimfhwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:beer-off-filled" /></template>

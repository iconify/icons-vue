<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxb7krdgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxb7krdgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-up-4-square-fill" /></template>

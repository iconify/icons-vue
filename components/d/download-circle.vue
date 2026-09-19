<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga9gewffn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ga9gewffn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:download-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3b6p42rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3b6p42rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-record-sharp-fill" /></template>
